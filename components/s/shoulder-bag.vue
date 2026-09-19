<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tn_s-dbef.css';
import '../../css/s/sdia6zb7q.css';
import '../../css/q/qjj7xz7uz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFND0weWo"><g class="s9cl3zbei"><path class="tn_s-dbef"/><path class="sdia6zb7q"/><circle class="qjj7xz7uz"/></g></mask></defs><path mask="url(#SVGFND0weWo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shoulder-bag" /></template>
