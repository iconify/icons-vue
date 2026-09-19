<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbsf62b3k.css';
import '../../css/p/pwvlvn-7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbsf62b3k"/><path class="pwvlvn-7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:manpage" /></template>
