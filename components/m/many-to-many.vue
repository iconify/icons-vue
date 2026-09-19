<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m4jss5ybp.css';
import '../../css/t/tnf0mrb5w.css';
import '../../css/b/bf1x1db8j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsIJRkcnI"><g class="s9cl3zbei"><path class="m4jss5ybp"/><path class="tnf0mrb5w"/><path class="bf1x1db8j"/></g></mask></defs><path mask="url(#SVGsIJRkcnI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:many-to-many" /></template>
