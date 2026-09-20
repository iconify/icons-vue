<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy4ogql_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xy4ogql_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:musicbrainz-picard-dark" /></template>
