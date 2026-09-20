<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlbfz3bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlbfz3bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nederlandsespoorwegen" /></template>
