<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejk70mm4e.css';
import '../../css/a/agnov_a2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejk70mm4e"/><path class="agnov_a2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:unfi" /></template>
