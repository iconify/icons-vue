<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noee0qjqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noee0qjqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-flag-outline" /></template>
