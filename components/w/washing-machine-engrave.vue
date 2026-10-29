<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pw23ckb-m.css';
import '../../css/d/dzdu3tbka.css';
import '../../css/r/rwx8arbdh.css';
import '../../css/d/dbwmo8bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pw23ckb-m wm-k"/><path class="dzdu3tbka wm-shadow"/><path class="rwx8arbdh wm-k"/><path class="dbwmo8bvj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:washing-machine-engrave" /></template>
