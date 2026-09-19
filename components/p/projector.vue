<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmqsevbxu.css';
import '../../css/c/c-21ecbzm.css';
import '../../css/u/umx108bql.css';
import '../../css/c/c4vps_bgo.css';
import '../../css/l/l7kugy4ne.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyWf9Cejo"><g class="ft5dv1b6b"><path class="hmqsevbxu"/><path class="c-21ecbzm"/><path class="umx108bql"/><circle class="c4vps_bgo"/><circle class="l7kugy4ne"/></g></mask></defs><path mask="url(#SVGyWf9Cejo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:projector" /></template>
