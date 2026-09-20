<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_h3vz--o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-edit-off-outline" /></template>
<style>
.c_h3vz--o {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.667.48-1.141Q3.96 5 4.635 5h.173l4 4H4v8.385q0 .269.173.442t.443.173h7.23v1zM21 6.616V9h-9.361l-4-4H9.05l1.433 2.844l.156.156h2.919l-1.5-3h2.5l1.5 3h3l-1.5-3h1.826q.691 0 1.153.463T21 6.616m.115 7.444l-.925-.945zm-1.588 2.853l-2.21-2.21l2.246-2.22q.148-.124.306-.188q.157-.064.315-.064q.172 0 .337.064t.302.193l.925.945q.123.148.187.308q.065.159.065.319t-.061.322t-.191.31zm1.846 4.652l-.714.714l-3.251-3.246l-.968.967h-2.21v-2.21l.968-.948L1.721 3.341l.713-.714zm-6.258-2.45h.95l.71-.715l-.944-.944l-.715.71z");
}

</style>
