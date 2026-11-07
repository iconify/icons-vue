<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpv5vhdla.css';
import '../../css/v/vlgypgk6o.css';
import '../../css/x/xs5tnub4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="vlgypgk6o"/><path class="xs5tnub4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-circle-bold-duotone" /></template>
