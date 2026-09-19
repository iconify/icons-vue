<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6pd-lbze.css';
import '../../css/r/rr-fqzblh.css';
import '../../css/u/u4ilukxus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="q6pd-lbze"/><rect class="rr-fqzblh"/><rect class="u4ilukxus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rows-3-filled" /></template>
