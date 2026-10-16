<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx-0v6v5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx-0v6v5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sound-wave-scan" /></template>
