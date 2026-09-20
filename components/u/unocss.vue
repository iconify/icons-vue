<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb1n6kb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb1n6kb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:unocss" /></template>
