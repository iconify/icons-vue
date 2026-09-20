<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gamzveg8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gamzveg8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:salesforce" /></template>
