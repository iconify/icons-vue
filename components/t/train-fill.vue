<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5zb0lb0o.css';
import '../../css/n/nlgid0bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5zb0lb0o"/><path clip-rule="evenodd" class="nlgid0bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:train-fill" /></template>
