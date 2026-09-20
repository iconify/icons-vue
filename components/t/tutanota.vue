<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8jqmu-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq8jqmu-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tutanota" /></template>
