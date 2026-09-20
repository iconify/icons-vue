<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6wnk9bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6wnk9bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:prefect" /></template>
