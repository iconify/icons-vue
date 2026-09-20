<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqk0_3bfl.css';
import '../../css/l/lgb7uffyh.css';
import '../../css/s/syaz7gedi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqk0_3bfl"/><path class="lgb7uffyh"/><path class="syaz7gedi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-stamp-document-bold" /></template>
