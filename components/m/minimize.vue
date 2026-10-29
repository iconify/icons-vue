<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-tys13rn.css';
import '../../css/n/ne7bzbcsu.css';
import '../../css/u/ui6r1kbdd.css';
import '../../css/w/wkvfpv47j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-tys13rn wm-k"/><path class="ne7bzbcsu wm-a"/><path class="ui6r1kbdd wm-k"/><path class="wkvfpv47j wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:minimize" /></template>
