<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bthykg66v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bthykg66v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-stop" /></template>
