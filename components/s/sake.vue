<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb1lu2blg.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/u/umy13yz7p.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGIsKoDbZJ" class="jb1lu2blg"/></defs><g class="n1mjunbsu"><path class="umy13yz7p"/><use href="#SVGIsKoDbZJ"/></g><use href="#SVGIsKoDbZJ" class="ij2x_72vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sake" /></template>
