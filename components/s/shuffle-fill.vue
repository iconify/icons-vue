<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llh0qcb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llh0qcb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-fill" /></template>
