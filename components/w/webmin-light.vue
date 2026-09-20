<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to8eil6jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="to8eil6jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webmin-light" /></template>
