<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsh_v_bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsh_v_bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stackframe-light" /></template>
