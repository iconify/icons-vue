<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7y90fksk.css';
import '../../css/d/dkbffkbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7y90fksk"/><path class="dkbffkbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-open-bold" /></template>
