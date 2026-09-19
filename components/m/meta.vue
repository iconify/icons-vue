<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaa_3geeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaa_3geeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:meta" /></template>
