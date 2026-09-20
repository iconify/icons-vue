<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdxxvebub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxxvebub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:youtube" /></template>
