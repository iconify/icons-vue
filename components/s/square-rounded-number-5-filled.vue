<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv5_fs9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snv5_fs9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-5-filled" /></template>
