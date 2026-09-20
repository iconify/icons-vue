<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a53go_wkz.css';
import '../../css/c/ck-pzhbhq.css';
import '../../css/c/c7gp0hbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a53go_wkz"/><path class="ck-pzhbhq"/><path class="c7gp0hbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mnd" /></template>
