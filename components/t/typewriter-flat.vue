<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7vqxtz8c.css';
import '../../css/j/jenqg7b4f.css';
import '../../css/o/ocwt-0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q7vqxtz8c"/><path class="jenqg7b4f"/><path class="ocwt-0blw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:typewriter-flat" /></template>
