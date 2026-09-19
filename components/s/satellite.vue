<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6nbwb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa6nbwb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:satellite" /></template>
