<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1cz-gh7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1cz-gh7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:table-outline" /></template>
