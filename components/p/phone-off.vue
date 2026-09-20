<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5wc5cr_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5wc5cr_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-off" /></template>
