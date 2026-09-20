<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk9tf_p6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk9tf_p6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:uninstall-line" /></template>
