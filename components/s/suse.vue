<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl72_acfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl72_acfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:suse" /></template>
