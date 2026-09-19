<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m4jss5ybp.css';
import '../../css/u/urj19wz9n.css';
import '../../css/k/k9zewywgp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSQJqBKGw"><g class="s9cl3zbei"><path class="m4jss5ybp"/><path class="urj19wz9n"/><path class="k9zewywgp"/></g></mask></defs><path mask="url(#SVGSQJqBKGw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:one-to-many" /></template>
