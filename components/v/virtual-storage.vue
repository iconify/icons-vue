<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyv7zbbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyv7zbbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:virtual-storage" /></template>
