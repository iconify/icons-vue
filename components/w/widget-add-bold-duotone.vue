<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuv2pzbjk.css';
import '../../css/b/b2f0rdb6m.css';
import '../../css/l/lmwlcacsv.css';
import '../../css/x/xp8rjqbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuv2pzbjk"/><path class="b2f0rdb6m"/><path class="lmwlcacsv"/><path class="xp8rjqbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-add-bold-duotone" /></template>
