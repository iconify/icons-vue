<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f68bxi0py.css';
import '../../css/h/h35_mschr.css';
import '../../css/s/s3gwzxt1c.css';
import '../../css/i/i9hh53bve.css';
import '../../css/n/nx4fo20-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f68bxi0py wm-shadow"/><path class="h35_mschr wm-k"/><path class="s3gwzxt1c wm-k"/><path class="i9hh53bve wm-a"/><path class="nx4fo20-h wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:tornado" /></template>
