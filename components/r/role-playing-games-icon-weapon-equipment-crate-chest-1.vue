<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f8_yxzbej.css';
import '../../css/g/g3azem9gj.css';
import '../../css/z/z-dp3fbdb.css';
import '../../css/n/n5kknrbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f8_yxzbej"/><path class="g3azem9gj"/><path class="z-dp3fbdb"/><path class="n5kknrbif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:role-playing-games-icon-weapon-equipment-crate-chest-1" /></template>
