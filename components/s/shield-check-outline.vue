<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io5xcjbzm.css';
import '../../css/q/qwjuf14gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io5xcjbzm"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-check-outline" /></template>
