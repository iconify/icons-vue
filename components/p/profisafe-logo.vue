<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1mcvkjvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1mcvkjvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:profisafe-logo" /></template>
