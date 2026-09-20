<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj71yl0qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj71yl0qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:up-down-duotone" /></template>
