<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apiedpb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1280};
const content = `<path class="apiedpb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sign-in" /></template>
