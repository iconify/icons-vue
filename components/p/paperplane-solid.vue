<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6us-9ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6us-9ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paperplane-solid" /></template>
