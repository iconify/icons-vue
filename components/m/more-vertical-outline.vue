<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwapf4b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uwapf4b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:more-vertical-outline" /></template>
