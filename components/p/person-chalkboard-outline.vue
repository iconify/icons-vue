<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap9k2cboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap9k2cboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:person-chalkboard-outline" /></template>
