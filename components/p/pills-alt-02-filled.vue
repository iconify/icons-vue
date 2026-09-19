<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e32pzmbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e32pzmbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pills-alt-02-filled" /></template>
