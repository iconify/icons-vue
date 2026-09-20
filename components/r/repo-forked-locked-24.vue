<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peg2icuzl.css';
import '../../css/p/prhwfbcjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peg2icuzl"/><path class="prhwfbcjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-forked-locked-24" /></template>
