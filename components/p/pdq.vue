<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz8z7jozz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8z7jozz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pdq" /></template>
