<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs-zd6s9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs-zd6s9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:split-outline" /></template>
