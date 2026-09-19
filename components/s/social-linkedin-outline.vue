<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtsijlbvl.css';
import '../../css/x/x67r1rb3u.css';
import '../../css/k/kf_wzi21l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jtsijlbvl"/><path clip-rule="evenodd" class="x67r1rb3u"/><path class="kf_wzi21l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-linkedin-outline" /></template>
