<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1q542b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k1q542b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-with-open-arms" /></template>
