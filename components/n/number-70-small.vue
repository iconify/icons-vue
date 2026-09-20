<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpcu1cy2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpcu1cy2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-70-small" /></template>
