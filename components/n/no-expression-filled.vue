<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb8nn8bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8nn8bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:no-expression-filled" /></template>
