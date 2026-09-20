<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9iz5sboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9iz5sboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pretzel" /></template>
