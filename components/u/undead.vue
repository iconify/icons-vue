<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo282mbbg.css';
import '../../css/t/tj13mnmfk.css';
import '../../css/v/v8bzv4b3x.css';
import '../../css/y/yry9ecckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo282mbbg"/><path clip-rule="evenodd" class="tj13mnmfk"/><path class="v8bzv4b3x"/><path clip-rule="evenodd" class="yry9ecckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:undead" /></template>
