<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfh6k-b6z.css';
import '../../css/t/t0tp8r25e.css';
import '../../css/y/y23y2_vlw.css';
import '../../css/n/nin82pzcn.css';
import '../../css/o/o5_n4ybok.css';
import '../../css/t/t4sxrgblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="hfh6k-b6z"/><path class="t0tp8r25e"/><path clip-rule="evenodd" class="y23y2_vlw"/><path clip-rule="evenodd" class="nin82pzcn"/><path clip-rule="evenodd" class="o5_n4ybok"/><path clip-rule="evenodd" class="t4sxrgblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:settings" /></template>
