<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k70enmbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k70enmbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tallymark-4" /></template>
