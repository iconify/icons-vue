<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj-378b7y.css';
import '../../css/n/nblq3cbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj-378b7y"/><path class="nblq3cbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:mic-fill" /></template>
