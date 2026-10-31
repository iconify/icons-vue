<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7x-4e4hm.css';
import '../../css/x/x_t76jq2h.css';
import '../../css/f/fhw0kygnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="u7x-4e4hm"/><path class="x_t76jq2h"/><path class="fhw0kygnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:republic-congo" /></template>
