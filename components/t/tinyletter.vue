<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea6a2ebin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea6a2ebin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tinyletter" /></template>
