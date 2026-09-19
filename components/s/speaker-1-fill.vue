<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ksm5bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c7ksm5bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-1-fill" /></template>
