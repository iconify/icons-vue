<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-ssoxb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ssoxb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:users-group-outline" /></template>
