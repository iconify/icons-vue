<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/glzuhhbww.css';
import '../../css/l/lnr6n0bgh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvfl6ddBJ"><g class="aql7dnt-u"><path class="glzuhhbww"/><path class="lnr6n0bgh"/></g></mask></defs><path mask="url(#SVGvfl6ddBJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:minus-the-top" /></template>
