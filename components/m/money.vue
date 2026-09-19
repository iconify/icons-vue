<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs5ksoa2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs5ksoa2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:money" /></template>
