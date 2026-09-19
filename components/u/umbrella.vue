<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3v73bb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3v73bb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:umbrella" /></template>
