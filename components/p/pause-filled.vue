<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaev_d16p.css';
import '../../css/a/a8l7vd6df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="zaev_d16p"/><rect class="a8l7vd6df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pause-filled" /></template>
