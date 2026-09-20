<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzkb3gzut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzkb3gzut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:person-add-2" /></template>
