<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lczir7byp.css';
import '../../css/u/umplx46gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lczir7byp"/><path class="umplx46gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:notebook-duotone" /></template>
