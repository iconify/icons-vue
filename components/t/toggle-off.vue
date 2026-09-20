<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zml8k9bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zml8k9bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:toggle-off" /></template>
