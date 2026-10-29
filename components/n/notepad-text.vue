<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb5ltkbul.css';
import '../../css/g/g6qgqxezo.css';
import '../../css/v/vioieb06c.css';
import '../../css/p/pfwk5xe4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb5ltkbul wm-a"/><path class="g6qgqxezo wm-a"/><path class="vioieb06c wm-a"/><path class="pfwk5xe4m wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:notepad-text" /></template>
