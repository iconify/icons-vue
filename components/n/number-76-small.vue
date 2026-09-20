<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl41wdvll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl41wdvll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-76-small" /></template>
