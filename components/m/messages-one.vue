<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/p/p4skm9fjy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9cPLNZWq"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="p4skm9fjy"/></g></mask></defs><path mask="url(#SVG9cPLNZWq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:messages-one" /></template>
