<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05adabyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a05adabyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pluralsight" /></template>
