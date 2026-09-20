<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icv3hsb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:traffic-jam-outline-sharp" /></template>
<style>
.icv3hsb9s {
  fill: currentColor;
  d: path("M3.23 21H2v-8l2.237-5.327h9.84l2.23 5.33V21h-1.23v-1.904H3.231zm.224-8.98h11.394l-1.402-3.347H4.862zM3 18.095h12.308V13.02H3zm3.351-1.735q.322-.313.322-.785t-.326-.803t-.794-.33t-.788.33t-.323.803t.327.785t.793.312t.789-.312m7.192 0q.323-.313.323-.785t-.327-.803t-.793-.33t-.79.33t-.321.803t.326.785t.793.312q.467 0 .79-.312M18 18.154v-7.792l-1.864-4.458h-9.48l.421-1h9.715L19 10.154v8zm2.77-2.846V7.516l-1.845-4.381H9.521l.421-1h9.654l2.173 5.192v7.98zm-11.616.25");
}

</style>
