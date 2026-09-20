<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqom69dqx.css';
import '../../css/v/vonci7bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqom69dqx"/><path class="vonci7bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:newspaper-solid" /></template>
