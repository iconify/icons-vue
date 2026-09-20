<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2k8ptcj.css';
import '../../css/r/rm4r7y8ko.css';
import '../../css/f/fixn44brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2k8ptcj"/><path class="rm4r7y8ko"/><path class="fixn44brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:vault" /></template>
