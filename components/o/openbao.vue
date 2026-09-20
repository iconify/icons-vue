<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i63w6ibri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i63w6ibri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:openbao" /></template>
