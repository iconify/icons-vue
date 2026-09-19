<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/x/xqlu89iqi.css';
import '../../css/s/s-3szabqp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqpZjXbFX"><g class="ft5dv1b6b"><path class="arj7difgh"/><path class="xqlu89iqi"/><path class="s-3szabqp"/></g></mask></defs><path mask="url(#SVGqpZjXbFX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:voice-message" /></template>
