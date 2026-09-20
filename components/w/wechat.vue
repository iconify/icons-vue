<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clr0thirl.css';
import '../../css/c/ci_39onbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clr0thirl"/><path class="ci_39onbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wechat" /></template>
