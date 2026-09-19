<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fpx-00njb.css';
import '../../css/c/cvij5gvui.css';
import '../../css/h/h80grackm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2RlOychi"><g class="s9cl3zbei"><circle class="fpx-00njb"/><path class="cvij5gvui"/><path class="h80grackm"/></g></mask></defs><path mask="url(#SVG2RlOychi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:unlock-one" /></template>
