<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/afq7mjurd.css';
import '../../css/e/eiol0ep0o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHp2ribKM"><g class="v3_i3wktz"><path class="afq7mjurd"/><path class="eiol0ep0o"/></g></mask></defs><path mask="url(#SVGHp2ribKM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-incoming" /></template>
