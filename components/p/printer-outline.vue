<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df_ehdiwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df_ehdiwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:printer-outline" /></template>
