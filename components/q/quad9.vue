<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u87apxb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u87apxb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quad9" /></template>
