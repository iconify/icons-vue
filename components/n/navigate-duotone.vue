<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vundi_b1g.css';
import '../../css/z/zqqdl4nxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vundi_b1g"/><path class="zqqdl4nxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:navigate-duotone" /></template>
