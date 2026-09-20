<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozaqti53i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozaqti53i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:moon-solid" /></template>
