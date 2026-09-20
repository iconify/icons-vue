<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdvk43bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvk43bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:smile-circle-solid" /></template>
