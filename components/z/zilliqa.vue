<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz15zbcnl.css';
import '../../css/n/ngd8w9bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz15zbcnl"/><path class="ngd8w9bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zilliqa" /></template>
