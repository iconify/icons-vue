<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hvqy7zb2s.css';
import '../../css/c/c5drbra_w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7wUwycJl"><g class="ufeehvblu"><path class="hvqy7zb2s"/><path class="c5drbra_w"/></g></mask></defs><path mask="url(#SVG7wUwycJl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rss" /></template>
