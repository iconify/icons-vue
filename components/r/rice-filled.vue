<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8y9q0bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g8y9q0bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rice-filled" /></template>
