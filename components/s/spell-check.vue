<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpx7y9xrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpx7y9xrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spell-check" /></template>
