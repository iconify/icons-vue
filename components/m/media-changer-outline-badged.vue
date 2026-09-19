<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kon2j4bpd.css';
import '../../css/m/mjknonirp.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kon2j4bpd"/><path class="mjknonirp"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-outline-badged" /></template>
