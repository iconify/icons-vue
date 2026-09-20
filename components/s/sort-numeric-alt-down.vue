<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4a8etro.css';
import '../../css/v/vl8d-nbty.css';
import '../../css/s/shthbcb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4a8etro"/><path class="vl8d-nbty"/><path class="shthbcb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-numeric-alt-down" /></template>
