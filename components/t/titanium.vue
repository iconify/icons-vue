<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl-ss2b6i.css';
import '../../css/d/dpkyovbsu.css';
import '../../css/o/ozgmnyspl.css';
import '../../css/z/zy6lb4bby.css';
import '../../css/n/nrw9sebpg.css';
import '../../css/e/er332lbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVG2ZVolbVK"><circle class="yl-ss2b6i"/></clipPath></defs><g clip-path="url(#SVG2ZVolbVK)"><path class="dpkyovbsu"/></g><ellipse transform="rotate(-30 256 256)" class="ozgmnyspl"/><circle class="zy6lb4bby"/><circle class="nrw9sebpg"/><circle class="er332lbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:titanium" /></template>
