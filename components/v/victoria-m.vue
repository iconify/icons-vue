<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5rwtnb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5rwtnb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:victoria-m" /></template>
