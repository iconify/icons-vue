<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw8zzfb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw8zzfb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:runkeeper" /></template>
