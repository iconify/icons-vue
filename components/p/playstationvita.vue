<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ciad33t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ciad33t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playstationvita" /></template>
