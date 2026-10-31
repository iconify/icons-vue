<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpav4_btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpav4_btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:outdent" /></template>
