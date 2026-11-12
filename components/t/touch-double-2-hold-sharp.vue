<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_5qggbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2-hold-sharp" /></template>
<style>
.u_5qggbut {
  fill: currentColor;
  d: path("m3.006 9.514l-.97.282q-.03-.198-.043-.392t-.012-.398q.017-2.927 2.045-4.966T8.981 2t4.973 2.04T16 9.006q0 .154-.003.283l-.008.277l-1.014-.424q.023-1.205-.384-2.257q-.406-1.052-1.131-1.87q-.825-.917-1.971-1.466T8.98 3q-2.5 0-4.25 1.753T2.98 9.006q0 .136.01.25q.009.115.015.258m2.802-.897l-1.02.314q.016-.87.34-1.616q.324-.748.903-1.3q.56-.557 1.317-.892q.758-.335 1.633-.335q.252 0 .5.03t.496.097l-.323.952q-.173-.036-.334-.058q-.16-.02-.34-.02q-1.224 0-2.125.814T5.808 8.617m3.25-.925v4.289h2.269V6.192h1v5.789H19V21H9.244l-5.613-7.165L4.666 12.8l3.392 2.079V7.692z");
}

</style>
