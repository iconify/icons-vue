<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/rzge4sb3y.css';
import '../../css/u/uowmflbel.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGO7QlTCPD"><g class="ufeehvblu"><path class="rzge4sb3y"/><path class="uowmflbel"/></g></mask></defs><path mask="url(#SVGO7QlTCPD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:setting" /></template>
