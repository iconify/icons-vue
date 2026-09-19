<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/t3j6luy7a.css';
import '../../css/u/uowmflbel.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9e55ocrc"><g class="ufeehvblu"><path class="t3j6luy7a"/><path class="uowmflbel"/></g></mask></defs><path mask="url(#SVG9e55ocrc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:setting-one" /></template>
