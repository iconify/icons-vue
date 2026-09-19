<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/vho2rjtrw.css';
import '../../css/m/m-ojbcwmy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzNw0cdOJ"><g class="v3_i3wktz"><rect class="vho2rjtrw"/><path class="m-ojbcwmy"/></g></mask></defs><path mask="url(#SVGzNw0cdOJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shopping-bag-one" /></template>
