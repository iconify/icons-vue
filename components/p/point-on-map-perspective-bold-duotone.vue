<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg5jd3b1a.css';
import '../../css/a/a__o3db_x.css';
import '../../css/a/aaaprebjw.css';
import '../../css/v/v3dddsvcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5jd3b1a"/><path class="a__o3db_x"/><path class="aaaprebjw"/><path class="v3dddsvcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-perspective-bold-duotone" /></template>
