<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqjc2cbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqjc2cbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-settings-fill" /></template>
