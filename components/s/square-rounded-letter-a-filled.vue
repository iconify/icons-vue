<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrn53_cik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrn53_cik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-a-filled" /></template>
