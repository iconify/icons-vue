<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnckipbnp.css';
import '../../css/h/hlxdn7yed.css';
import '../../css/j/j92rn7wey.css';
import '../../css/f/fy7t5zukz.css';
import '../../css/n/nn4n7g3zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnckipbnp wm-k"/><path class="hlxdn7yed wm-a"/><path class="j92rn7wey wm-a"/><path class="fy7t5zukz wm-a"/><path class="nn4n7g3zi wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:microscope" /></template>
