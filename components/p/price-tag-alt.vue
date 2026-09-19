<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoz51dbyx.css';
import '../../css/r/r_b7lhsan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoz51dbyx"/><path class="r_b7lhsan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:price-tag-alt" /></template>
