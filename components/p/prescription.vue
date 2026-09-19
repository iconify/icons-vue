<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/q_fzk6ijs.css';
import '../../css/v/vb9_1lbgt.css';
import '../../css/w/w64ndbcxx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHYfQmdvP"><g class="s9cl3zbei"><path clip-rule="evenodd" class="q_fzk6ijs"/><path class="vb9_1lbgt"/><path class="w64ndbcxx"/></g></mask></defs><path mask="url(#SVGHYfQmdvP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:prescription" /></template>
