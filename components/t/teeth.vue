<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/eunooc4xb.css';
import '../../css/e/euiaxmb0w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfkb5ZcfK"><g class="s9cl3zbei"><path clip-rule="evenodd" class="eunooc4xb"/><path class="euiaxmb0w"/></g></mask></defs><path mask="url(#SVGfkb5ZcfK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:teeth" /></template>
