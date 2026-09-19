<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq_3n607q.css';
import '../../css/n/nblq3cbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq_3n607q"/><path class="nblq3cbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:mic-outline" /></template>
